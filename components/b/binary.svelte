<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3vq1sb0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a3vq1sb0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:binary" {...props}></Icon>
