<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h6is39r_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h6is39r_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cube-3d-line" {...props}></Icon>
