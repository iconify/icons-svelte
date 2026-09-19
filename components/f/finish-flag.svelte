<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fniq62c1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fniq62c1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:finish-flag" {...props}></Icon>
