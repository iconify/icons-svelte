<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2jz3n1-t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w2jz3n1-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bluetooth" {...props}></Icon>
