<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yo2crbouy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="yo2crbouy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:receipt-bold" {...props}></Icon>
