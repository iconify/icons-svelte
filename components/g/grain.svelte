<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u3k5vebsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":384};
const content = `<path class="u3k5vebsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:grain" {...props}></Icon>
