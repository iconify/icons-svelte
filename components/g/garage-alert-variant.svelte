<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/le2l0650x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="le2l0650x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:garage-alert-variant" {...props}></Icon>
