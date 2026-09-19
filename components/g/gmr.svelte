<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilxgl2y6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ilxgl2y6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:gmr" {...props}></Icon>
