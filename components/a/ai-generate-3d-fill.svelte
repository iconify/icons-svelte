<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qg7v921kl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qg7v921kl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-generate-3d-fill" {...props}></Icon>
