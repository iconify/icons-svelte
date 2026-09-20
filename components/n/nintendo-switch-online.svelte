<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i3gsrgbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i3gsrgbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:nintendo-switch-online" {...props}></Icon>
