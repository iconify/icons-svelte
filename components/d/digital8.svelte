<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a5xl8acvc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="a5xl8acvc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:digital8" {...props}></Icon>
