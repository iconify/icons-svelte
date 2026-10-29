<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p6kasu72k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="p6kasu72k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gemini-wordmark" {...props}></Icon>
