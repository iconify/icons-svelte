<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiv1j9a1m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiv1j9a1m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:file-video-plus" {...props}></Icon>
