<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/ru1ae30ek.css';
import '../../css/h/hbitvks7s.css';
import '../../css/a/am48ss4er.css';
import '../../css/w/wo_-lacfx.css';
import '../../css/k/kytzhiaey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ru1ae30ek"/><path class="hbitvks7s"/><path class="am48ss4er"/><path clip-rule="evenodd" class="wo_-lacfx"/><path class="kytzhiaey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:analytics" {...props}></Icon>
