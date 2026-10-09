<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmeg1tr8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mmeg1tr8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:forklift-20" {...props}></Icon>
