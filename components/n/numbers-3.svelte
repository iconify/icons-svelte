<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w59t3iw6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w59t3iw6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:numbers-3" {...props}></Icon>
