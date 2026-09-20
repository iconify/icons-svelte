<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rw7xbrb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rw7xbrb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:ghostty-light" {...props}></Icon>
