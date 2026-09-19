<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zv29q5vwm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zv29q5vwm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:pfsense-logo" {...props}></Icon>
