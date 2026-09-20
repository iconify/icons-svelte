<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pnfwjq3mb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pnfwjq3mb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:gamepad-round-left" {...props}></Icon>
