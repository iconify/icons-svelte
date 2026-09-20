<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q_pn7accy.css';
import '../../css/c/czydtacky.css';
import '../../css/p/psskj8yuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="q_pn7accy"/><path class="czydtacky"/><path class="psskj8yuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:beauty-cosmatic-lip-stick" {...props}></Icon>
