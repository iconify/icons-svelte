<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/to_00xq7r.css';
import '../../css/s/sd17u1b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="to_00xq7r"/><path class="sd17u1b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:fastify" {...props}></Icon>
