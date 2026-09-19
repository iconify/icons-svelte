<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yb8qd6bbu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="yb8qd6bbu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:linkedin" {...props}></Icon>
