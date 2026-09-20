<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m4r3m-bjq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m4r3m-bjq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:cloud-server" {...props}></Icon>
