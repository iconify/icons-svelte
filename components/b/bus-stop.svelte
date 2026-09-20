<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0td4lb9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n0td4lb9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:bus-stop" {...props}></Icon>
