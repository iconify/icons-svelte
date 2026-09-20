<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4u8pbwjc.css';
import '../../css/a/atiyfgbwu.css';
import '../../css/p/p1l1mibxh.css';
import '../../css/x/x8poo_bjf.css';
import '../../css/g/g25jkbcju.css';
import '../../css/z/zc5vmwzag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<g class="x4u8pbwjc"><circle class="atiyfgbwu"/><path class="p1l1mibxh"/></g><g class="x8poo_bjf"><circle class="atiyfgbwu"/><path class="g25jkbcju"/><path class="zc5vmwzag"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:person-fencing" {...props}></Icon>
