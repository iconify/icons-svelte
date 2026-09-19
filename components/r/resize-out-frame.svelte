<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/l/lhti6p55o.css';
import '../../css/k/kdw727bvn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<g class="n1lsf0bnc"><path class="lhti6p55o"/><path class="kdw727bvn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:resize-out-frame" {...props}></Icon>
