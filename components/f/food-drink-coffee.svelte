<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2xq81-vx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="k2xq81-vx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:food-drink-coffee" {...props}></Icon>
