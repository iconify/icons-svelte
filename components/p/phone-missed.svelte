<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/omwx7-b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":384};
const content = `<path class="omwx7-b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:phone-missed" {...props}></Icon>
