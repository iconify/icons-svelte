<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vbpyf9uav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="vbpyf9uav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:google-drive-logo-bottom-blue" {...props}></Icon>
