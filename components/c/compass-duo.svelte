<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lafhkbbho.css';
import '../../css/m/moy2nm1qy.css';
import '../../css/w/w4vxnac6h.css';
import '../../css/g/g2v04sb6l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="lafhkbbho"/><path class="moy2nm1qy"/><path class="w4vxnac6h"/><path class="g2v04sb6l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:compass-duo" {...props}></Icon>
