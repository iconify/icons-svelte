<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1rvn5bri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1rvn5bri"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:letter-v-bulk-round" {...props}></Icon>
