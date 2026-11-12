<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s33ndsrce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s33ndsrce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alarmpi-light" {...props}></Icon>
