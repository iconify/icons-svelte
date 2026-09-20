<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v55oqqhae.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v55oqqhae"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-stop" {...props}></Icon>
