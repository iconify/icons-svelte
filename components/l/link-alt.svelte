<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl9-1ibeu.css';
import '../../css/m/m3no34b0f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl9-1ibeu"/><path class="m3no34b0f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:link-alt" {...props}></Icon>
