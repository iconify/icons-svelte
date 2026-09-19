<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5ig-ib6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="i5ig-ib6j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:play" {...props}></Icon>
