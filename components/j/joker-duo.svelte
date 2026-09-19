<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i7z2n2wtr.css';
import '../../css/d/dznf5ccgt.css';
import '../../css/x/xerbc4b9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="i7z2n2wtr"/><path class="dznf5ccgt"/><path class="xerbc4b9w"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:joker-duo" {...props}></Icon>
