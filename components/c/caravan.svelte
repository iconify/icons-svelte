<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r5wgb97jk.css';
import '../../css/j/j2fbvgb4b.css';
import '../../css/e/ekwl493ik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r5wgb97jk"/><path class="j2fbvgb4b"/><path class="ekwl493ik"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:caravan" {...props}></Icon>
