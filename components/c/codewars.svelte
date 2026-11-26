<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofk5kdpol.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="ofk5kdpol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:codewars" {...props}></Icon>
