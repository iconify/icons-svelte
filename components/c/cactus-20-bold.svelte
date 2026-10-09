<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w1of7cc9l.css';
import '../../css/b/bw6ycksak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w1of7cc9l"/><path class="bw6ycksak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cactus-20-bold" {...props}></Icon>
