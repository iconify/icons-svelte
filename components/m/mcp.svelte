<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm-9v2lvg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bm-9v2lvg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:mcp" {...props}></Icon>
