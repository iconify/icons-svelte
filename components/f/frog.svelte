<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi284xblo.css';
import '../../css/r/rl9nm6b5b.css';
import '../../css/j/j3g_okd9a.css';
import '../../css/s/s7hiajbok.css';
import '../../css/r/rryepq1cz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fi284xblo"/><path class="rl9nm6b5b"/><path class="j3g_okd9a"/><path class="s7hiajbok"/><path class="rryepq1cz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:frog" {...props}></Icon>
