<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gttixbbjg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gttixbbjg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:book-open-page-variant-outline" {...props}></Icon>
