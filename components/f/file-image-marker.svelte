<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jf57yobvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jf57yobvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-image-marker" {...props}></Icon>
