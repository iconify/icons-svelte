<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/piycljbom.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="piycljbom"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:picture" {...props}></Icon>
