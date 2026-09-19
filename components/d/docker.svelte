<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mczf-vpsj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="mczf-vpsj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:docker" {...props}></Icon>
