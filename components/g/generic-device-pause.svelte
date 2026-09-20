<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pzjpz52lt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pzjpz52lt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-pause" {...props}></Icon>
