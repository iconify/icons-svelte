<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1w90i-5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m1w90i-5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clipboard-check-stroke-12" {...props}></Icon>
