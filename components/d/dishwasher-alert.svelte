<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xaod-urcv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xaod-urcv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:dishwasher-alert" {...props}></Icon>
