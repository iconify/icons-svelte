<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpz7tqcjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":50,"height":50};
const content = `<path class="fpz7tqcjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="map:police" {...props}></Icon>
