<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s4n0chxiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4n0chxiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:plug-3-line" {...props}></Icon>
