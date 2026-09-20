<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bss_qy-zr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="bss_qy-zr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:petri-dish-lab-equipment-solid" {...props}></Icon>
