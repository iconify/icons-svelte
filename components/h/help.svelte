<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tq625fsze.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="tq625fsze"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:help" {...props}></Icon>
