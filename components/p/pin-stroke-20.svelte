<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxjqwnk_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nxjqwnk_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pin-stroke-20" {...props}></Icon>
