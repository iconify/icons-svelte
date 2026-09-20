<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wn77a-bgw.css';
import '../../css/i/ipbi0zqsr.css';
import '../../css/f/fgp57luau.css';
import '../../css/h/hbufu4b4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wn77a-bgw"/><path class="ipbi0zqsr"/><path class="fgp57luau"/><path class="hbufu4b4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:nanoclaw" {...props}></Icon>
