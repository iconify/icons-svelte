<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mng4_v46u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mng4_v46u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:printer-3d-nozzle" {...props}></Icon>
