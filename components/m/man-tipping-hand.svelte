<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3pnzib4i.css';
import '../../css/d/dqshecczl.css';
import '../../css/c/c3w9l72hp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d3pnzib4i"/><path class="dqshecczl"/><path class="c3w9l72hp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:man-tipping-hand" {...props}></Icon>
