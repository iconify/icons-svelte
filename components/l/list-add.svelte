<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ktj9py5wg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ktj9py5wg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:list-add" {...props}></Icon>
