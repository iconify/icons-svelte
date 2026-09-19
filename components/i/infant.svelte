<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/p/p5x0b0j1d.css';
import '../../css/r/r4f9anbfl.css';
import '../../css/y/y183xbbsw.css';
import '../../css/n/n891lmcsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="p5x0b0j1d"/><path class="r4f9anbfl"/><path class="y183xbbsw"/><path class="n891lmcsl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:infant" {...props}></Icon>
