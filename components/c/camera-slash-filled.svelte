<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/innh25fao.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="innh25fao"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:camera-slash-filled" {...props}></Icon>
