<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pl-87t-9d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pl-87t-9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bus-with-destination-display-and-pantograph" {...props}></Icon>
