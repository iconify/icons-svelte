<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xswyrebgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xswyrebgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:music-artist-fill" {...props}></Icon>
