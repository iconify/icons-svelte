<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jormnbcqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="jormnbcqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:axial-reflecting-dish-with-monopod-antenna-and-beams" {...props}></Icon>
