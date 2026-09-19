<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hygm70ygz.css';
import '../../css/j/jxl7ousbe.css';
import '../../css/g/gb1t6vkyv.css';
import '../../css/e/e3k02oyaf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hygm70ygz"/><path class="jxl7ousbe"/><circle class="gb1t6vkyv"/><path class="e3k02oyaf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-audio-light" {...props}></Icon>
