<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbgu8eb0z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hbgu8eb0z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:agent-ai" {...props}></Icon>
