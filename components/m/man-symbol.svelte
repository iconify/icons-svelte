<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5e6vsrrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="l5e6vsrrs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:man-symbol" {...props}></Icon>
