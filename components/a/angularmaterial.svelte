<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2ub9vb4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="f2ub9vb4k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:angularmaterial" {...props}></Icon>
