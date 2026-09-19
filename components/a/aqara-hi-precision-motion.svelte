<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuu17jmxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iuu17jmxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:aqara-hi-precision-motion" {...props}></Icon>
