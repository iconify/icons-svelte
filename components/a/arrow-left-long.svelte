<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e30u10b9n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e30u10b9n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrow-left-long" {...props}></Icon>
