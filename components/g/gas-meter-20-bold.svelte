<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbys_lb8n.css';
import '../../css/y/ykkgrkb-l.css';
import '../../css/d/d-kptbbco.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fbys_lb8n"/><path class="ykkgrkb-l"/><path class="d-kptbbco"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:gas-meter-20-bold" {...props}></Icon>
