<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whte9obio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="whte9obio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:folder-add-1-filled" {...props}></Icon>
