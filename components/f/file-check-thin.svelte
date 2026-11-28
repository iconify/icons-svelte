<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on15oyn-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="on15oyn-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-check-thin" {...props}></Icon>
