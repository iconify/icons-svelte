<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k7zq275ci.css';
import '../../css/f/fzcjrqbtu.css';
import '../../css/t/tg66l2b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k7zq275ci"/><path class="fzcjrqbtu"/><path class="tg66l2b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:ladle-bold" {...props}></Icon>
