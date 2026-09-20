<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1_dzw0-a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1_dzw0-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:folder-music-line" {...props}></Icon>
