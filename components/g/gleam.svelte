<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5tfq2sjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a5tfq2sjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:gleam" {...props}></Icon>
