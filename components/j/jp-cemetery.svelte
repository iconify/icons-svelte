<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-y81wbnx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d-y81wbnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:jp-cemetery" {...props}></Icon>
