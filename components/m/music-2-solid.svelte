<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol8x4ezvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ol8x4ezvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:music-2-solid" {...props}></Icon>
