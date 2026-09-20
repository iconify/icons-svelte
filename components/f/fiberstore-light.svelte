<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/enxy2xb4q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="enxy2xb4q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fiberstore-light" {...props}></Icon>
