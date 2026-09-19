<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvuj97b5z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wvuj97b5z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:graph" {...props}></Icon>
