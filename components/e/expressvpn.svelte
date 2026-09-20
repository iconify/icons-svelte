<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re6akhb_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="re6akhb_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:expressvpn" {...props}></Icon>
