<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pc32zubtm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pc32zubtm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:pulse-ai-line" {...props}></Icon>
