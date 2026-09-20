<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rz0bm-2uj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rz0bm-2uj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:folder-refresh" {...props}></Icon>
