<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2k6suboh.css';
import '../../css/w/wsn4cdbga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d2k6suboh"/><path class="wsn4cdbga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:immersion-heater-20" {...props}></Icon>
