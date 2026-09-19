<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3d5ixbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m3d5ixbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:playlist-repeat-song-fill" {...props}></Icon>
