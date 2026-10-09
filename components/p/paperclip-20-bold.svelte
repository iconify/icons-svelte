<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bn8v5vbkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bn8v5vbkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:paperclip-20-bold" {...props}></Icon>
