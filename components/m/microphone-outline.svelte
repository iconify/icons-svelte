<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qmp-gsbor.css';
import '../../css/b/boghcbc6a.css';
import '../../css/s/s2tvgacgn.css';
import '../../css/g/gjsv9w97d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="qmp-gsbor"/><path class="boghcbc6a"/><path clip-rule="evenodd" class="s2tvgacgn"/><path class="gjsv9w97d"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:microphone-outline" {...props}></Icon>
