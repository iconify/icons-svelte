<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/roylc0i0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="roylc0i0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:layout-align-right" {...props}></Icon>
