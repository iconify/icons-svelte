<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnylsg0-q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pnylsg0-q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:important" {...props}></Icon>
