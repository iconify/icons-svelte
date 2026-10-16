<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fscbk5btm.css';
import '../../css/i/i1rcpxbal.css';
import '../../css/l/lk_wy274k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fscbk5btm"/><path class="i1rcpxbal"/><path class="lk_wy274k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gangway-20-bold" {...props}></Icon>
