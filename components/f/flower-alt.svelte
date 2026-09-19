<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vphlp94-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":456};
const content = `<path class="vphlp94-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:flower-alt" {...props}></Icon>
