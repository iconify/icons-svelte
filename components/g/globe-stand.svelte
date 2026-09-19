<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/asoc6abfb.css';
import '../../css/c/cyzgarbmo.css';
import '../../css/r/refo3vb5p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="asoc6abfb"/><path class="cyzgarbmo"/><path class="refo3vb5p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:globe-stand" {...props}></Icon>
