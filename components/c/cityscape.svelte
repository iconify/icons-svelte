<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z7aq2f48w.css';
import '../../css/h/hkb5eob8z.css';
import '../../css/r/rdh1s06mo.css';
import '../../css/t/to5_hpm1w.css';
import '../../css/w/wd5pmyb3s.css';
import '../../css/s/sj1_vcqik.css';
import '../../css/g/ghzrfub8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<rect class="z7aq2f48w"/><path class="hkb5eob8z"/><path class="rdh1s06mo"/><g class="to5_hpm1w"><path class="wd5pmyb3s"/><path class="sj1_vcqik"/><path class="ghzrfub8c"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:cityscape" {...props}></Icon>
