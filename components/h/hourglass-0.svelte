<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lbqz0xbia.css';
import '../../css/a/aqdcgn30f.css';
import '../../css/s/sikw3pb2u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="lbqz0xbia"/><path class="aqdcgn30f"/><path clip-rule="evenodd" class="sikw3pb2u"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:hourglass-0" {...props}></Icon>
