<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chu0w4bzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="chu0w4bzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:cutlery-stroke-12" {...props}></Icon>
