<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dux41cbwc.css';
import '../../css/j/jgb2w2b3k.css';
import '../../css/i/itdz_wb-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":16};
const content = `<path class="dux41cbwc"/><path class="jgb2w2b3k"/><path class="itdz_wb-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="formkit:export" {...props}></Icon>
