<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fb9_lwbtc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="fb9_lwbtc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-shrink-diagonal-1" {...props}></Icon>
