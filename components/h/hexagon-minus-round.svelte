<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f01fuoakt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f01fuoakt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:hexagon-minus-round" {...props}></Icon>
