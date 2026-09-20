<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/efxcg-bdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="efxcg-bdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-ai-fill" {...props}></Icon>
