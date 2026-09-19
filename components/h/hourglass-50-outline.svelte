<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bv1mx0xds.css';
import '../../css/v/vvhyatv6v.css';
import '../../css/v/veq-chbsf.css';
import '../../css/f/f10zp4qwq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="bv1mx0xds"/><path clip-rule="evenodd" class="vvhyatv6v"/><path class="veq-chbsf"/><path clip-rule="evenodd" class="f10zp4qwq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:hourglass-50-outline" {...props}></Icon>
