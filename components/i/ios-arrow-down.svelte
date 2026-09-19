<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7z1vnbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h7z1vnbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-arrow-down" {...props}></Icon>
