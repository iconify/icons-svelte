<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/am770-rkn.css';
import '../../css/d/d2e0hniif.css';
import '../../css/o/on4mi1mmc.css';
import '../../css/j/jhaw5gzhp.css';
import '../../css/s/sor7622zl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="am770-rkn"/><path clip-rule="evenodd" class="d2e0hniif"/><path class="on4mi1mmc"/><circle class="jhaw5gzhp"/><circle class="sor7622zl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:grin" {...props}></Icon>
