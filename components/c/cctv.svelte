<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eg2fy-b0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="eg2fy-b0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:cctv" {...props}></Icon>
