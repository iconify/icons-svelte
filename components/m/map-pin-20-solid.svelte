<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zynfyurpj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="zynfyurpj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:map-pin-20-solid" {...props}></Icon>
