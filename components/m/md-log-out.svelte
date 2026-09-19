<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vi-wnz67i.css';
import '../../css/e/eopo7lbmx.css';
import '../../css/p/p4xyc1bjj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vi-wnz67i"/><path class="eopo7lbmx"/><path class="p4xyc1bjj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-log-out" {...props}></Icon>
