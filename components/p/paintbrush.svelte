<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tw0wrli5t.css';
import '../../css/p/pixrq9syg.css';
import '../../css/y/ybvkvjmwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tw0wrli5t"/><path class="pixrq9syg"/><path class="ybvkvjmwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:paintbrush" {...props}></Icon>
