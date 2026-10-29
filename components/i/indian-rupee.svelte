<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro7tz4bzv.css';
import '../../css/h/h_ffhdx3r.css';
import '../../css/e/e1_59bbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro7tz4bzv wm-k"/><path class="h_ffhdx3r wm-a"/><path class="e1_59bbxb wm-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:indian-rupee" {...props}></Icon>
