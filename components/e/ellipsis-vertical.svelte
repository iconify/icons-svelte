<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3fjp7b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":512};
const content = `<path class="f3fjp7b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:ellipsis-vertical" {...props}></Icon>
