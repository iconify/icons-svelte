<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_y4tmboz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_y4tmboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:flash-off-sharp" {...props}></Icon>
