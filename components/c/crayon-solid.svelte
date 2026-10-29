<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ku9zw5_gl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ku9zw5_gl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:crayon-solid" {...props}></Icon>
