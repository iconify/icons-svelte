<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/epgl_be4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="epgl_be4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:dry-line" {...props}></Icon>
