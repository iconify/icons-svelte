<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mdjwufbrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mdjwufbrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:led-variant-off" {...props}></Icon>
