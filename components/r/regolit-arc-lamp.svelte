<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nt9e-_ble.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nt9e-_ble"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:regolit-arc-lamp" {...props}></Icon>
