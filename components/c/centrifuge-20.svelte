<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqgqpt0as.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gqgqpt0as"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:centrifuge-20" {...props}></Icon>
