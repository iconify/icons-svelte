<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-t034vxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w-t034vxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:moon-stars" {...props}></Icon>
