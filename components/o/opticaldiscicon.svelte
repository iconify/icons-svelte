<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b4lt3lb1x.css';
import '../../css/i/i6r1xobqq.css';
import '../../css/e/e2kroochg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b4lt3lb1x"/><path class="i6r1xobqq"/><path class="e2kroochg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:opticaldiscicon" {...props}></Icon>
