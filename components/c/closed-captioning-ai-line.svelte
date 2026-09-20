<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oc6clwbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oc6clwbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:closed-captioning-ai-line" {...props}></Icon>
