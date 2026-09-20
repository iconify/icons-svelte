<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-hk2hbee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k-hk2hbee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:checkerboard" {...props}></Icon>
