<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kt0_y9e1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kt0_y9e1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:chevron-top" {...props}></Icon>
