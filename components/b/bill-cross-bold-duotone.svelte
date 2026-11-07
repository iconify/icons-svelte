<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtol7-b-x.css';
import '../../css/d/dma0xkbxb.css';
import '../../css/u/u36hnrvrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtol7-b-x"/><path class="dma0xkbxb"/><path class="u36hnrvrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-cross-bold-duotone" {...props}></Icon>
