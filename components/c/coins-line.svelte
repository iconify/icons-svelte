<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgpx8zbru.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fgpx8zbru"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:coins-line" {...props}></Icon>
