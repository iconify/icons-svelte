<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zs2rhf85g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zs2rhf85g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:dice" {...props}></Icon>
