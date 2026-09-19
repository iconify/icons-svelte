<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/msgv33qhw.css';
import '../../css/n/np_h2lbss.css';
import '../../css/a/ay1ozab3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="msgv33qhw"/><path class="np_h2lbss"/><path class="ay1ozab3a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs-poly:align-items-center" {...props}></Icon>
