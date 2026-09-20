<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp17d_muq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp17d_muq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dribbble-box" {...props}></Icon>
