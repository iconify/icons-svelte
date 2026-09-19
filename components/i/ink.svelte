<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss8d_8bwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ss8d_8bwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:ink" {...props}></Icon>
