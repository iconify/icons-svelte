<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ial_4vbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ial_4vbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-round-right" {...props}></Icon>
