<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/knlvkn1xk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="knlvkn1xk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brain-ai-3-line" {...props}></Icon>
