<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tjymv8b0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="tjymv8b0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:clock-14" {...props}></Icon>
