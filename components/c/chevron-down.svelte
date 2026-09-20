<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0iiyl8ji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0iiyl8ji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:chevron-down" {...props}></Icon>
