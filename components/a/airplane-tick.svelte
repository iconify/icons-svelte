<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iviu9lava.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iviu9lava"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:airplane-tick" {...props}></Icon>
