<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pi9p0vbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pi9p0vbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:chevron-up-circle" {...props}></Icon>
