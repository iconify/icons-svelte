<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhrmt3b3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mhrmt3b3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ev-plug-ccs2" {...props}></Icon>
