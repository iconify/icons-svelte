<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccwkw3plu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ccwkw3plu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:flip-vertical-line" {...props}></Icon>
