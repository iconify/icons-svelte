<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u4y1kvb4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="u4y1kvb4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:location-fill-12" {...props}></Icon>
