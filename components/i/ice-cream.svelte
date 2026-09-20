<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h7q45q27k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h7q45q27k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:ice-cream" {...props}></Icon>
