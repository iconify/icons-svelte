<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gc6c15taa.css';
import '../../css/p/pnnjfds4j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gc6c15taa"/><path class="pnnjfds4j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:music-library" {...props}></Icon>
