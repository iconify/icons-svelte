<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyvd_y2uw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kyvd_y2uw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:reddit-alien" {...props}></Icon>
