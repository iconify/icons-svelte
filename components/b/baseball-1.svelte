<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wbaw4rvsq.css';
import '../../css/e/ep44yib3r.css';
import '../../css/u/ut-8af0wp.css';
import '../../css/g/g56ggcc8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="wbaw4rvsq"/><path class="ep44yib3r"/><path class="ut-8af0wp"/><path class="g56ggcc8j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:baseball-1" {...props}></Icon>
