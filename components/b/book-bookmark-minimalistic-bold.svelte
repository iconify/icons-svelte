<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcgmm_a3s.css';
import '../../css/v/v11avebgt.css';
import '../../css/t/thx30ob7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mcgmm_a3s"/><path class="v11avebgt"/><path class="thx30ob7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:book-bookmark-minimalistic-bold" {...props}></Icon>
