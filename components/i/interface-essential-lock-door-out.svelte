<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ncg24tb6p.css';
import '../../css/w/w4z9bpbgj.css';
import '../../css/c/cak1_0e_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ncg24tb6p"/><path class="w4z9bpbgj"/><path class="cak1_0e_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:interface-essential-lock-door-out" {...props}></Icon>
