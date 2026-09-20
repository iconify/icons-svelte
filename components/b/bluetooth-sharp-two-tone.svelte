<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wj8mcob3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wj8mcob3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bluetooth-sharp-two-tone" {...props}></Icon>
