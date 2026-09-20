<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fwk4ow2yn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fwk4ow2yn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:homebridge" {...props}></Icon>
