<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipx_1529y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ipx_1529y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:filter-heart" {...props}></Icon>
