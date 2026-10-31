<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bl8o6hhxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bl8o6hhxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drag-horizontal-bulk-round" {...props}></Icon>
