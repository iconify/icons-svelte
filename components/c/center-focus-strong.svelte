<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/abfn7falh.css';
import '../../css/p/pupgf8bdc.css';
import '../../css/a/a1lb80bow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="abfn7falh"/><rect class="pupgf8bdc"/><path class="a1lb80bow"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:center-focus-strong" {...props}></Icon>
