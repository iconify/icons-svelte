<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bsh3mybya.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bsh3mybya"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-dock-left" {...props}></Icon>
