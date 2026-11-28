<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ream2rr8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ream2rr8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:car-check" {...props}></Icon>
