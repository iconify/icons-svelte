<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/g/gpxs-3vco.css';
import '../../css/l/l6e6t_bwu.css';
import '../../css/z/zg9huqb-e.css';
import '../../css/f/fhdjwwbrg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gpxs-3vco"/><path class="l6e6t_bwu"/><path class="zg9huqb-e"/><path class="fhdjwwbrg"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bill-2-bold-duotone" {...props}></Icon>
