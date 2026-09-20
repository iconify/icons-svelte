<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qu0jvlbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qu0jvlbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-safety" {...props}></Icon>
