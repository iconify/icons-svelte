<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu-8-1byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xu-8-1byn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:play-circle" {...props}></Icon>
