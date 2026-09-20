<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/r/rnfomkb1n.css';
import '../../css/d/dt0ocrz6j.css';
import '../../css/m/mzih8kb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="n1lsf0bnc"><path class="rnfomkb1n"/><path clip-rule="evenodd" class="dt0ocrz6j"/><path class="mzih8kb1j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:openclaw-moltbot-clawdbot" {...props}></Icon>
