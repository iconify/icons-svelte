<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u8__b9zxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8__b9zxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:cctv" {...props}></Icon>
