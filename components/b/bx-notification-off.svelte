<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv4rrqlkh.css';
import '../../css/h/h68a5vtzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fv4rrqlkh"/><circle class="h68a5vtzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-notification-off" {...props}></Icon>
