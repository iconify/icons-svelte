<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bsssxmnnx.css';
import '../../css/r/rp3ollbom.css';
import '../../css/o/on8g3mivh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bsssxmnnx"/><path class="rp3ollbom"/><path class="on8g3mivh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:lightning-1-duo" {...props}></Icon>
