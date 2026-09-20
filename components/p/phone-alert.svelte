<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ra_rfb9hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ra_rfb9hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:phone-alert" {...props}></Icon>
