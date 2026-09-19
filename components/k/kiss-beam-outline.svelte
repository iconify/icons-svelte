<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zuyycrb6d.css';
import '../../css/i/izzti6-0z.css';
import '../../css/g/gamxx9z1h.css';
import '../../css/n/nuh5gzbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="zuyycrb6d"/><path clip-rule="evenodd" class="izzti6-0z"/><path class="gamxx9z1h"/><path clip-rule="evenodd" class="nuh5gzbto"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:kiss-beam-outline" {...props}></Icon>
