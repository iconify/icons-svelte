<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rll_-bcvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="rll_-bcvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:rock" {...props}></Icon>
