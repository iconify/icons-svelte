<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chu4txbfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chu4txbfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:code-block-line" {...props}></Icon>
