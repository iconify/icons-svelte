<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/anec31bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="anec31bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:accessibility" {...props}></Icon>
