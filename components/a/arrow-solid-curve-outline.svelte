<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g9yv_e71e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<path clip-rule="evenodd" class="g9yv_e71e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:arrow-solid-curve-outline" {...props}></Icon>
