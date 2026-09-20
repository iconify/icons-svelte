<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myl30ub-w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="myl30ub-w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:generic-device-alarm" {...props}></Icon>
