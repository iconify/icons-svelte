<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u0-3p01nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u0-3p01nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:jedi-order" {...props}></Icon>
