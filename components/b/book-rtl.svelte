<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwbsocnoy.css';
import '../../css/p/pfpnh2nsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xwbsocnoy"/><path class="pfpnh2nsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:book-rtl" {...props}></Icon>
