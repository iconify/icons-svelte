<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhkdtwb2h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="jhkdtwb2h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:hand" {...props}></Icon>
