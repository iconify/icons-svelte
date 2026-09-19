<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pcn2r4bsf.css';
import '../../css/k/kvlndpbwg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pcn2r4bsf"/><path class="kvlndpbwg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-python" {...props}></Icon>
