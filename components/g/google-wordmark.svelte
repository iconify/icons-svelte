<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv8gbu0fn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="fv8gbu0fn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:google-wordmark" {...props}></Icon>
