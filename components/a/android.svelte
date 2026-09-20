<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sgzr6pbzp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sgzr6pbzp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:android" {...props}></Icon>
