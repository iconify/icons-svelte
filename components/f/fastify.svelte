<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uujfweb9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="uujfweb9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:fastify" {...props}></Icon>
