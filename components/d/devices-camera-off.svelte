<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w8if3ytuf.css';
import '../../css/y/yywevybdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="w8if3ytuf"/><path class="yywevybdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-camera-off" {...props}></Icon>
