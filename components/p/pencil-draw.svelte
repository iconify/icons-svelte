<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cl37b7c_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cl37b7c_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:pencil-draw" {...props}></Icon>
