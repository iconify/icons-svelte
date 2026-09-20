<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmok5rrec.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rmok5rrec"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:arrow-big-down-short-sharp-duotone" {...props}></Icon>
