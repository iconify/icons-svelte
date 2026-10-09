<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/px_2uxb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="px_2uxb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pentagon-20-bold" {...props}></Icon>
