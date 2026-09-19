<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm83ibnhs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="rm83ibnhs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:check-circle" {...props}></Icon>
