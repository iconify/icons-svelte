<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sriwl8bgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sriwl8bgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:plug" {...props}></Icon>
