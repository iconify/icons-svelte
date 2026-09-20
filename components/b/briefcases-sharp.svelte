<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4u0-9bit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4u0-9bit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:briefcases-sharp" {...props}></Icon>
