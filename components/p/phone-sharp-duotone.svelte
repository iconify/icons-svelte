<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ruxv4vbmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ruxv4vbmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:phone-sharp-duotone" {...props}></Icon>
