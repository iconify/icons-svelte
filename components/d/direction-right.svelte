<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i9ck89bsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="i9ck89bsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:direction-right" {...props}></Icon>
