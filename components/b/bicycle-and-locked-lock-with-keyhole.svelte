<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sl9lvtbbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="sl9lvtbbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bicycle-and-locked-lock-with-keyhole" {...props}></Icon>
