<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/swk2k98ux.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="swk2k98ux"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-folder-song-solid" {...props}></Icon>
