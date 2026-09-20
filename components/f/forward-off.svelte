<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kfn4ue8nh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kfn4ue8nh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:forward-off" {...props}></Icon>
