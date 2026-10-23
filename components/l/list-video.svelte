<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/khk_fyb0m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="khk_fyb0m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:list-video" {...props}></Icon>
