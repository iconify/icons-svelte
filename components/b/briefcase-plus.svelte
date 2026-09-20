<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rram23-dq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rram23-dq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:briefcase-plus" {...props}></Icon>
