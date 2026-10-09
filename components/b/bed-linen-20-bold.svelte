<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ritmkr3yi.css';
import '../../css/k/kmw8fq5zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ritmkr3yi"/><path class="kmw8fq5zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:bed-linen-20-bold" {...props}></Icon>
