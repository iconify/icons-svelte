<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtt9_ab8z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtt9_ab8z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:ai-agent-line" {...props}></Icon>
