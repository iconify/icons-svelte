<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qylr5_b2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qylr5_b2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:apps-2-ai-fill" {...props}></Icon>
