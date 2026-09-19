<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1rj7u0mj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="y1rj7u0mj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:qwik" {...props}></Icon>
