<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vubcf06gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vubcf06gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:close-square-light" {...props}></Icon>
