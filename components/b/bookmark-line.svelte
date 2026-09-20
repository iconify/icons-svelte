<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p07581b0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p07581b0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:bookmark-line" {...props}></Icon>
