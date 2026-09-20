<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ip9gr5baz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ip9gr5baz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:air-humidifier" {...props}></Icon>
