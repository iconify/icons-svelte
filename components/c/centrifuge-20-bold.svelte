<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkkixhb6n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rkkixhb6n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:centrifuge-20-bold" {...props}></Icon>
