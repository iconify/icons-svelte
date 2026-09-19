<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic52moyir.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="ic52moyir"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:reddit" {...props}></Icon>
