<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl43i_bvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl43i_bvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:paint-brush-line" {...props}></Icon>
