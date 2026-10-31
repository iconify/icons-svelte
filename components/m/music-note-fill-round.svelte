<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qp4c5_b0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qp4c5_b0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:music-note-fill-round" {...props}></Icon>
