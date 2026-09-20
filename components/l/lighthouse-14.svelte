<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5hobibwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="i5hobibwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:lighthouse-14" {...props}></Icon>
