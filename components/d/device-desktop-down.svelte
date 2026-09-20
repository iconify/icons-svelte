<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m78b3fx0g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m78b3fx0g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-desktop-down" {...props}></Icon>
