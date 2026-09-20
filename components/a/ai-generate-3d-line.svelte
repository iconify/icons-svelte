<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8itlj66h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8itlj66h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-generate-3d-line" {...props}></Icon>
