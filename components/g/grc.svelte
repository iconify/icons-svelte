<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r_i1oy07h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r_i1oy07h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:grc" {...props}></Icon>
