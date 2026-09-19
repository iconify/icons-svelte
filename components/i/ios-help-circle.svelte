<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3-g7fbod.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b3-g7fbod"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:ios-help-circle" {...props}></Icon>
