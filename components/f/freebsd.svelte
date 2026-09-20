<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e5_uwzbdg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e5_uwzbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:freebsd" {...props}></Icon>
