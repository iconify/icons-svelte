<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yg4w013as.css';
import '../../css/z/z0xcrnbqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":65,"height":64};
const content = `<path class="yg4w013as"/><path class="z0xcrnbqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:i-imaging-alternative-pet" {...props}></Icon>
