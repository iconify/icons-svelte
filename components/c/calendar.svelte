<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4v3gmdhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":432};
const content = `<path class="t4v3gmdhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:calendar" {...props}></Icon>
