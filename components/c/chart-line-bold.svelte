<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/j/juq13gbkq.css';
import '../../css/h/hijqlccze.css';
import '../../css/u/uhfj7cbdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="juq13gbkq"/><path class="hijqlccze"/><path class="uhfj7cbdk"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:chart-line-bold" {...props}></Icon>
