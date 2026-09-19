<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8rgxcbzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="d8rgxcbzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:google-plus-g" {...props}></Icon>
