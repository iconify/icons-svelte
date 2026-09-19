<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ar-x8db-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="ar-x8db-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:filter-list" {...props}></Icon>
