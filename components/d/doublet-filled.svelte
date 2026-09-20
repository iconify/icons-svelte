<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu6qnqe0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xu6qnqe0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:doublet-filled" {...props}></Icon>
