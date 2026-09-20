<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bykwrac3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="bykwrac3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:chevron-close" {...props}></Icon>
