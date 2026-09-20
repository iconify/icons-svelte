<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-4xk6b_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i-4xk6b_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-heart-outline" {...props}></Icon>
