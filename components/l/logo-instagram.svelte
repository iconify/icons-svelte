<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nlr4lquzx.css';
import '../../css/v/vdsszm8qt.css';
import '../../css/f/fheposbhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<circle class="nlr4lquzx"/><path class="vdsszm8qt"/><path class="fheposbhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-instagram" {...props}></Icon>
