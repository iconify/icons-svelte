<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tym262xzo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tym262xzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-arrow-right" {...props}></Icon>
