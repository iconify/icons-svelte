<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ej4l518vs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ej4l518vs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-ball" {...props}></Icon>
