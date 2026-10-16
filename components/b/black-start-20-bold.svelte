<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hn0um0h7v.css';
import '../../css/l/lpo20xysi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hn0um0h7v"/><path class="lpo20xysi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:black-start-20-bold" {...props}></Icon>
