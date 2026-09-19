<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-63y2w0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":408,"height":488};
const content = `<path class="l-63y2w0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:plurk" {...props}></Icon>
