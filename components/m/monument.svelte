<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz75x3bje.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rz75x3bje"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:monument" {...props}></Icon>
