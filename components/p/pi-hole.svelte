<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nvn9fpbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nvn9fpbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pi-hole" {...props}></Icon>
