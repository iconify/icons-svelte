<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/f-ntwsbcy.css';
import '../../css/i/i6-20-b6o.css';
import '../../css/g/gpy5opbyj.css';
import '../../css/a/aonm-8qcs.css';
import '../../css/x/xiv5klbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="f-ntwsbcy"/><path class="i6-20-b6o"/><path class="gpy5opbyj"/><path class="aonm-8qcs"/><path class="xiv5klbfn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:rolling-eyes-duo" {...props}></Icon>
