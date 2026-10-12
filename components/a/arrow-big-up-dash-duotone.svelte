<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/uluoubbrd.css';
import '../../css/c/c225mmbyl.css';
import '../../css/l/l5ul_sbmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="uluoubbrd"/><path class="c225mmbyl"/><path class="l5ul_sbmh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:arrow-big-up-dash-duotone" {...props}></Icon>
