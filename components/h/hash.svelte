<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_o68g-cq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a_o68g-cq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:hash" {...props}></Icon>
