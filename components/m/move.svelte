<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itafvib0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itafvib0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:move" {...props}></Icon>
