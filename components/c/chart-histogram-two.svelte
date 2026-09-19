<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/ntnk9upyi.css';
import '../../css/t/twzr5ub1p.css';
import '../../css/b/batkyrymz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ntnk9upyi"/><path class="twzr5ub1p"/><path class="batkyrymz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:chart-histogram-two" {...props}></Icon>
