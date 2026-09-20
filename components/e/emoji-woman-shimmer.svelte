<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j13k_rbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j13k_rbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:emoji-woman-shimmer" {...props}></Icon>
