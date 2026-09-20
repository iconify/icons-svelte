<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akijnrkmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="akijnrkmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d-nozzle-heat" {...props}></Icon>
