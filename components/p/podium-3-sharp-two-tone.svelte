<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/l/lid049njr.css';
import '../../css/x/xeb-fib6w.css';
import '../../css/c/ciu-kx8bj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="lid049njr"/><path class="xeb-fib6w"/><path class="ciu-kx8bj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:podium-3-sharp-two-tone" {...props}></Icon>
