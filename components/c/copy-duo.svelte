<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/t/tbjwq7z1x.css';
import '../../css/i/i61tymsyr.css';
import '../../css/b/bzs2jobta.css';
import '../../css/v/vidyn3b5f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="tbjwq7z1x"/><path class="i61tymsyr"/><path class="bzs2jobta"/><path class="vidyn3b5f"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:copy-duo" {...props}></Icon>
