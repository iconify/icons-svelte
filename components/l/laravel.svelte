<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb8c01ug.css';
import '../../css/k/ki6om5blk.css';
import '../../css/w/w3blszelr.css';
import '../../css/g/g97xns1ip.css';
import '../../css/y/yyx32dxar.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="ki6om5blk"/><path class="w3blszelr"/><path class="g97xns1ip"/><path class="yyx32dxar"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:laravel" {...props}></Icon>
