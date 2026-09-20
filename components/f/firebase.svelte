<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l__hojbyl.css';
import '../../css/h/hrxhp9b1x.css';
import '../../css/d/d6mqo8bss.css';
import '../../css/q/qp9ttxbyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l__hojbyl"/><path class="hrxhp9b1x"/><path class="d6mqo8bss"/><path class="qp9ttxbyq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:firebase" {...props}></Icon>
