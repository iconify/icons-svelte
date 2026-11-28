<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ldqit5bct.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ldqit5bct"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:image-plus" {...props}></Icon>
