<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kf6dfce5y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="kf6dfce5y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bench-with-plaque-and-armrests" {...props}></Icon>
