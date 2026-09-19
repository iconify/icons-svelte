<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s-lo8vbld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s-lo8vbld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:flash-sharp" {...props}></Icon>
