<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zcu0apbtk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":25,"height":24};
const content = `<path class="zcu0apbtk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:camera-movie-1" {...props}></Icon>
