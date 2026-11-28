<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i0axupq2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i0axupq2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:image-arrow-down" {...props}></Icon>
