<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f9ul_lbcj.css';
import '../../css/r/r32kt6-tp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="f9ul_lbcj"/><path class="r32kt6-tp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ei:archive" {...props}></Icon>
