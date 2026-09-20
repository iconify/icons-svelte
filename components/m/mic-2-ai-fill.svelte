<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ie_oe4beb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ie_oe4beb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mic-2-ai-fill" {...props}></Icon>
