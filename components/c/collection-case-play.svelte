<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m5c-sgb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":456};
const content = `<path class="m5c-sgb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:collection-case-play" {...props}></Icon>
