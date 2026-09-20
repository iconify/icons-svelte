<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfp322jpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfp322jpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-shield" {...props}></Icon>
