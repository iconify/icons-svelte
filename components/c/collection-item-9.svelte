<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkafytb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="xkafytb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-9" {...props}></Icon>
