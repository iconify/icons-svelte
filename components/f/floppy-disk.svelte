<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g56tg2bmy.css';
import '../../css/d/dmp8t0bvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="g56tg2bmy"/><path class="dmp8t0bvq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:floppy-disk" {...props}></Icon>
