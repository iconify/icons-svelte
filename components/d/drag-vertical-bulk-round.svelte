<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o77se9lzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o77se9lzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:drag-vertical-bulk-round" {...props}></Icon>
