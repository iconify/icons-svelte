<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l32lerbfx.css';
import '../../css/l/l6_t7qyjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="l32lerbfx"/><path class="l6_t7qyjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-gemini-ai-open" {...props}></Icon>
