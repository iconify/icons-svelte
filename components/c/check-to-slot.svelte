<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veq3ccc5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="veq3ccc5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:check-to-slot" {...props}></Icon>
