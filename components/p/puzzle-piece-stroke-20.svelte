<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxjg9cssi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="kxjg9cssi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:puzzle-piece-stroke-20" {...props}></Icon>
