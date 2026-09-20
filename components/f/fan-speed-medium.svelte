<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ymv_zcbtr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ymv_zcbtr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:fan-speed-medium" {...props}></Icon>
