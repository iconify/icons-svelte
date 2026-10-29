<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j6hkjtb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6hkjtb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:music-2" {...props}></Icon>
