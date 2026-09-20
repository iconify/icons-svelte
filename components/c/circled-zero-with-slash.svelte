<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_weg3b7j.css';
import '../../css/s/sxsjrzbyv.css';
import '../../css/g/goyqnobna.css';
import '../../css/r/r38bcib6d.css';
import '../../css/u/uhe3f6bup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<circle class="j_weg3b7j"/><g class="sxsjrzbyv"><circle class="goyqnobna"/><path class="r38bcib6d"/><path clip-rule="evenodd" class="uhe3f6bup"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:circled-zero-with-slash" {...props}></Icon>
