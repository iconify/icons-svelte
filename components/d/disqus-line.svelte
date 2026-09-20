<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlniswbpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zlniswbpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:disqus-line" {...props}></Icon>
