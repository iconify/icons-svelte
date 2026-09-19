<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm9z_xbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path clip-rule="evenodd" class="bm9z_xbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:debug-connected-compact" {...props}></Icon>
