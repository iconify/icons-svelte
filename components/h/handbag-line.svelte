<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kx_wdcbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kx_wdcbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:handbag-line" {...props}></Icon>
