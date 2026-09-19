<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a0sbubcuh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a0sbubcuh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:phoenix" {...props}></Icon>
