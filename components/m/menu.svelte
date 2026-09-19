<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwi40-g_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="lwi40-g_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:menu" {...props}></Icon>
