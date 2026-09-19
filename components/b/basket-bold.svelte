<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w3rz52jnr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="w3rz52jnr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:basket-bold" {...props}></Icon>
