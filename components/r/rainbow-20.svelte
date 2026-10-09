<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trz8ofble.css';
import '../../css/d/diva08b7c.css';
import '../../css/v/vxg-v0wsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="trz8ofble"/><path class="diva08b7c"/><path class="vxg-v0wsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rainbow-20" {...props}></Icon>
