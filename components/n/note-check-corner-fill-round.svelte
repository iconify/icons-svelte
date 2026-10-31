<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy2b_qbqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy2b_qbqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:note-check-corner-fill-round" {...props}></Icon>
