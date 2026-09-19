<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u1o1fw7_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="u1o1fw7_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:image-rotate" {...props}></Icon>
