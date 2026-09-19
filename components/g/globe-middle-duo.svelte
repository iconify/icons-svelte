<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/vk2uwtblc.css';
import '../../css/l/lbti0vbpg.css';
import '../../css/k/kx3lczbpu.css';
import '../../css/n/n8c6bo9hy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="vk2uwtblc"/><path clip-rule="evenodd" class="lbti0vbpg"/><path class="kx3lczbpu"/><path class="n8c6bo9hy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:globe-middle-duo" {...props}></Icon>
