<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxf5f-bxr.css';
import '../../css/j/jb9pwtbln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxf5f-bxr"/><path clip-rule="evenodd" class="jb9pwtbln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:message-3-text" {...props}></Icon>
