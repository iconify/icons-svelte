<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t7evv3bge.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t7evv3bge"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:clapperboard-ai-fill" {...props}></Icon>
