<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z0xk-nbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="z0xk-nbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nodejs" {...props}></Icon>
