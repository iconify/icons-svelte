<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/e8-14pblu.css';
import '../../css/w/whtc4r5ex.css';
import '../../css/o/ovr92_bin.css';
import '../../css/s/suljz2g3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path class="e8-14pblu"/><path clip-rule="evenodd" class="whtc4r5ex"/><path class="ovr92_bin"/><path clip-rule="evenodd" class="suljz2g3l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:question-circle-outline" {...props}></Icon>
