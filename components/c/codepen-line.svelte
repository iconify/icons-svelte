<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gxud0rbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gxud0rbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:codepen-line" {...props}></Icon>
