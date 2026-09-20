<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ig0u6q-wi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0u6q-wi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:openai-line" {...props}></Icon>
