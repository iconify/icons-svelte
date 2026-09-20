<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wpsxk_bqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":167.509};
const content = `<path class="wpsxk_bqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fastify-light" {...props}></Icon>
