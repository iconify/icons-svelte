<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fntjwp6sx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fntjwp6sx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:home" {...props}></Icon>
