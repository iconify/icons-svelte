<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lwrsxql2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="lwrsxql2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:mood" {...props}></Icon>
