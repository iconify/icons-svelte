<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jueoms9ry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jueoms9ry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:palace-fill" {...props}></Icon>
