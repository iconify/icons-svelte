<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tu-ylk7ly.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tu-ylk7ly"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:nature-ecology-green-house-glass-building-plants-crops-produce-farm" {...props}></Icon>
