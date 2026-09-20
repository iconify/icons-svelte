<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhp7qqclq.css';
import '../../css/i/ie_qpyhgo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhp7qqclq"/><path class="ie_qpyhgo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:chart-network" {...props}></Icon>
