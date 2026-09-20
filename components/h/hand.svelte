<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z20251bqj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z20251bqj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:hand" {...props}></Icon>
