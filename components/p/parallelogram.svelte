<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm5emubfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tm5emubfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:parallelogram" {...props}></Icon>
