<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/km-yg-bbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="km-yg-bbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:luna-dashboard-light" {...props}></Icon>
