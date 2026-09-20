<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ir_jl2baq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ir_jl2baq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:potted-flower-tulip-solid" {...props}></Icon>
