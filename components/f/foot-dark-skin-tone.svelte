<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj_n4-bzu.css';
import '../../css/q/qq4sgukxb.css';
import '../../css/z/z04drlb1l.css';
import '../../css/s/swak8ubny.css';
import '../../css/z/zja7hrpwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="jj_n4-bzu"/><path class="qq4sgukxb"/><g class="z04drlb1l"><path class="swak8ubny"/><path class="zja7hrpwx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:foot-dark-skin-tone" {...props}></Icon>
