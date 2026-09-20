<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnkyu7bdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dnkyu7bdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:location-pin-3-remix" {...props}></Icon>
