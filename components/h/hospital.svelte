<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/izi3e6qsl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="izi3e6qsl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:hospital" {...props}></Icon>
