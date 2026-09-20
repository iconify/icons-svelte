<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d9405_b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d9405_b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:open-envelope-right" {...props}></Icon>
