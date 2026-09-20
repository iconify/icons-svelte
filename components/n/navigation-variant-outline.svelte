<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5rh0obzn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y5rh0obzn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:navigation-variant-outline" {...props}></Icon>
