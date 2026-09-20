<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dsmsv2kzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dsmsv2kzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-2-fill" {...props}></Icon>
