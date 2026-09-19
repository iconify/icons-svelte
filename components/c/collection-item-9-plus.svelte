<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5_pm9b3h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":480};
const content = `<path class="g5_pm9b3h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-item-9-plus" {...props}></Icon>
