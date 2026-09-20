<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8oo7gb6g.css';
import '../../css/i/iz9p36q2i.css';
import '../../css/o/oaizj4bjv.css';
import '../../css/x/xjllsqnue.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<g class="n8oo7gb6g"><path class="iz9p36q2i"/><path class="oaizj4bjv"/><path class="xjllsqnue"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="marketeq:mp3-player" {...props}></Icon>
