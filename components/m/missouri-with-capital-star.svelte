<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mqtx79bpt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mqtx79bpt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:missouri-with-capital-star" {...props}></Icon>
