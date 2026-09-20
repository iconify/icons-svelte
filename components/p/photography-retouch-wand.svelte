<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxy3dwbbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fxy3dwbbq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:photography-retouch-wand" {...props}></Icon>
