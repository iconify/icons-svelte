<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkb26011h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wkb26011h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:memory" {...props}></Icon>
