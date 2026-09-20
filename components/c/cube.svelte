<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwcaxdhsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dwcaxdhsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:cube" {...props}></Icon>
