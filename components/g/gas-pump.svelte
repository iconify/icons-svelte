<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2tz1nbgx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2tz1nbgx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gas-pump" {...props}></Icon>
