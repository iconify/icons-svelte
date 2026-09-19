<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvbk_blhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mvbk_blhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:astro" {...props}></Icon>
