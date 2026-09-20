<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dmh9cs9my.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dmh9cs9my"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:gas-station" {...props}></Icon>
