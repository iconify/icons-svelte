<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lt4_7tbfr.css';
import '../../css/f/fe-32tbfb.css';
import '../../css/k/kyt4j6b-c.css';
import '../../css/s/ssw-3aboo.css';
import '../../css/x/xrgx2dblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="lt4_7tbfr"/><path class="fe-32tbfb"/><path class="kyt4j6b-c"/><path class="ssw-3aboo"/><path class="xrgx2dblx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:clapperboard-circle" {...props}></Icon>
