<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md80vybsv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="md80vybsv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:flagstick-with-pennant-in-hole" {...props}></Icon>
