<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-w_9x0ol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="r-w_9x0ol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:aspect-ratio" {...props}></Icon>
