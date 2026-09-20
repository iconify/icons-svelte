<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyyfu4bga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyyfu4bga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:pin-outline" {...props}></Icon>
