<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ivkxnnbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ivkxnnbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:gamepad-directional-line" {...props}></Icon>
