<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbyab0bzx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kbyab0bzx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:access-point-network-off" {...props}></Icon>
