<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n6p5pquqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n6p5pquqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:jstor" {...props}></Icon>
