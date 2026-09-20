<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lz8cwkb9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="lz8cwkb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:plane" {...props}></Icon>
