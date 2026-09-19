<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj62g-b9h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":408};
const content = `<path class="oj62g-b9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:google-drive" {...props}></Icon>
