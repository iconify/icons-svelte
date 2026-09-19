<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l704x-bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":440,"height":512};
const content = `<path class="l704x-bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:cuttlefish" {...props}></Icon>
