<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fc2_j6ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fc2_j6ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-tablet-filled" {...props}></Icon>
