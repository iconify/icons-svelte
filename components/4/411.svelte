<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n65uq_b4h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="n65uq_b4h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:411" {...props}></Icon>
