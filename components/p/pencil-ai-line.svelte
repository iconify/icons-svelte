<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nz8-0owbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nz8-0owbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pencil-ai-line" {...props}></Icon>
