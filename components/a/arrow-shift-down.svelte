<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s6u59sxkw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s6u59sxkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:arrow-shift-down" {...props}></Icon>
