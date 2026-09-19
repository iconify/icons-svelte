<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtf_51zyi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jtf_51zyi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-low-vision" {...props}></Icon>
