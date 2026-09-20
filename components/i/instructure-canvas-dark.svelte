<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eaqhmxb8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eaqhmxb8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:instructure-canvas-dark" {...props}></Icon>
