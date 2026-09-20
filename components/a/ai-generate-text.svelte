<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4w28ebjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w4w28ebjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-generate-text" {...props}></Icon>
