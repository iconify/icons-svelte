<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/daf5wab8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="daf5wab8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:folder-check-fill" {...props}></Icon>
