<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/i/i1kkrhrag.css';
import '../../css/r/r-z1rs2bk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i1kkrhrag"/><path clip-rule="evenodd" class="r-z1rs2bk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-minus-outline" {...props}></Icon>
