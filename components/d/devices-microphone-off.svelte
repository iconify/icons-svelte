<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vvk4_jk4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vvk4_jk4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:devices-microphone-off" {...props}></Icon>
