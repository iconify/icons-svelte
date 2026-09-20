<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm_0b6bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="wm_0b6bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:moon-12" {...props}></Icon>
