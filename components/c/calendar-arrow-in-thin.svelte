<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zglobacga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zglobacga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:calendar-arrow-in-thin" {...props}></Icon>
