<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgf8n7bep.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vgf8n7bep"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:api-1" {...props}></Icon>
