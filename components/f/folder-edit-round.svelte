<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzuv5c50q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzuv5c50q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:folder-edit-round" {...props}></Icon>
