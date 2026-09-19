<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhfvgrjhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zhfvgrjhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:crystal-earrings" {...props}></Icon>
