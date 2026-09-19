<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/liem6rbpc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":408};
const content = `<path class="liem6rbpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:local-see" {...props}></Icon>
