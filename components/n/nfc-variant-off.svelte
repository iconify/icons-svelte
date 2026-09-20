<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ponf9zbbh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ponf9zbbh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nfc-variant-off" {...props}></Icon>
