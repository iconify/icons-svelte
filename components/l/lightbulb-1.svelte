<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/ogxepvf0r.css';
import '../../css/k/kszy58azx.css';
import '../../css/o/ojqphszdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ogxepvf0r"/><path class="kszy58azx"/><path clip-rule="evenodd" class="ojqphszdh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:lightbulb-1" {...props}></Icon>
