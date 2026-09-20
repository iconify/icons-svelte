<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o-usqibey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-usqibey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d-nozzle-off" {...props}></Icon>
