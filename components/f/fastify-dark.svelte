<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h623n7bhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":167.509};
const content = `<path class="h623n7bhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastify-dark" {...props}></Icon>
