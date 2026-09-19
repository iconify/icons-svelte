<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hwz5aj3dz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hwz5aj3dz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:puzzle-piece" {...props}></Icon>
