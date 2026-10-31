<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qemcyt1xs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="qemcyt1xs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:car-in-gabled-building" {...props}></Icon>
