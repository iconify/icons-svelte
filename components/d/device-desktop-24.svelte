<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/drr5y5ebc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="drr5y5ebc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:device-desktop-24" {...props}></Icon>
