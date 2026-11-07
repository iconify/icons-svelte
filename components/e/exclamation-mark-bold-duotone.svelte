<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waxeanb4e.css';
import '../../css/m/mgns90b-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="waxeanb4e"/><path class="mgns90b-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:exclamation-mark-bold-duotone" {...props}></Icon>
