<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xf6tpenhx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xf6tpenhx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:rocketdotchat" {...props}></Icon>
