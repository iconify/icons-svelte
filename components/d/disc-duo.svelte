<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/g/gbtr3qbre.css';
import '../../css/l/lgqi0eb_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="gbtr3qbre"/><path class="lgqi0eb_q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:disc-duo" {...props}></Icon>
