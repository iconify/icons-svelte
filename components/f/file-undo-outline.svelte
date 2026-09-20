<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ds--vq8wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ds--vq8wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:file-undo-outline" {...props}></Icon>
