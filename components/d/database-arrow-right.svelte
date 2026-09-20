<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvtspfb2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvtspfb2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:database-arrow-right" {...props}></Icon>
