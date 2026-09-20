<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ypfau-f-d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ypfau-f-d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:phone-right-beside-exclamation-point" {...props}></Icon>
