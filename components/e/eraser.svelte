<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp6yps19e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zp6yps19e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:eraser" {...props}></Icon>
