<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r79mn2bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r79mn2bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-cog" {...props}></Icon>
