<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sxz5aqj2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sxz5aqj2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="healthicons:heartbeat-24px" {...props}></Icon>
