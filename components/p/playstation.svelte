<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/csa0j6xil.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="csa0j6xil"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:playstation" {...props}></Icon>
