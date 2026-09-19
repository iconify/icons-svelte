<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hc5xdf2ha.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hc5xdf2ha"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-emoji-high-contrast:folding-hand-fan" {...props}></Icon>
