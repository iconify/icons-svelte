<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu5vlxh4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vu5vlxh4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:donate-heart-filled" {...props}></Icon>
