<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/gk76gpujr.css';
import '../../css/s/sitli9irb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g class="n1lsf0bnc"><path class="gk76gpujr"/><path class="sitli9irb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:lamp-desk" {...props}></Icon>
