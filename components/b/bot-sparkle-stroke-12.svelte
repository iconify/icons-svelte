<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kuqh2nb0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="kuqh2nb0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bot-sparkle-stroke-12" {...props}></Icon>
