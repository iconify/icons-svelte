<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md2d0gm4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="md2d0gm4s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:arrow-up-1" {...props}></Icon>
