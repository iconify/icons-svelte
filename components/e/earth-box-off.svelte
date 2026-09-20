<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vhzm4jban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vhzm4jban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:earth-box-off" {...props}></Icon>
