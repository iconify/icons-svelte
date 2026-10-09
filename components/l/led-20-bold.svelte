<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruh8v-0xc.css';
import '../../css/e/eprzb-b7u.css';
import '../../css/r/r7o23obqg.css';
import '../../css/a/a21_wobxe.css';
import '../../css/q/ql5gy1bwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ruh8v-0xc"/><path class="eprzb-b7u"/><path class="r7o23obqg"/><path class="a21_wobxe"/><path class="ql5gy1bwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:led-20-bold" {...props}></Icon>
