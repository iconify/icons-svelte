<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv4g-3btx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv4g-3btx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:robber" {...props}></Icon>
