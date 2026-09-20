<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofc-ngbjx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ofc-ngbjx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heartbeat-fill" {...props}></Icon>
