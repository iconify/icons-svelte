<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pywiv_biz.css';
import '../../css/q/qv4_abryf.css';
import '../../css/c/c0wsg8bse.css';
import '../../css/y/yfoxxnbix.css';
import '../../css/r/rbeht2tnq.css';
import '../../css/i/ivikgibsc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pywiv_biz"/><path class="qv4_abryf"/><path class="c0wsg8bse"/><path class="yfoxxnbix"/><path class="rbeht2tnq"/><path class="ivikgibsc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bifacial-panel-20-bold" {...props}></Icon>
