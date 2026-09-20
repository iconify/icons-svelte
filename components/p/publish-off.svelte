<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q8e-2ibmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q8e-2ibmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:publish-off" {...props}></Icon>
