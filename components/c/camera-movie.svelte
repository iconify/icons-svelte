<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/imlplj1lz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="imlplj1lz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:camera-movie" {...props}></Icon>
