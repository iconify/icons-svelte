<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j1j10lb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j1j10lb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jsx" {...props}></Icon>
