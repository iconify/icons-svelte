<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ui7634x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i2ui7634x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:iframe-array" {...props}></Icon>
