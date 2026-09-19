<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hdzkbes4f.css';
import '../../css/j/jdlbr4k1q.css';
import '../../css/v/vsi98cbpj.css';
import '../../css/l/lb17mgb2c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="hdzkbes4f"/><path class="jdlbr4k1q"/><path clip-rule="evenodd" class="vsi98cbpj"/><path class="lb17mgb2c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:grid-remove-outline" {...props}></Icon>
