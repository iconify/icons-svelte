<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xt5lhvbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="xt5lhvbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:loop-1" {...props}></Icon>
