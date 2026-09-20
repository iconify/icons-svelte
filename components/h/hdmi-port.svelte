<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uvl4abcut.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uvl4abcut"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hdmi-port" {...props}></Icon>
