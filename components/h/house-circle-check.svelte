<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r54u05boz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r54u05boz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:house-circle-check" {...props}></Icon>
