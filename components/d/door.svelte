<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/os_tdyjga.css';
import '../../css/g/gcohp_b3e.css';
import '../../css/n/ndz3s8e5k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="os_tdyjga"/><path class="gcohp_b3e"/><path class="ndz3s8e5k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:door" {...props}></Icon>
