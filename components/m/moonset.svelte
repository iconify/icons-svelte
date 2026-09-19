<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl05jy16c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="rl05jy16c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:moonset" {...props}></Icon>
