<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_-2k6bgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":416};
const content = `<path class="s_-2k6bgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:blur" {...props}></Icon>
