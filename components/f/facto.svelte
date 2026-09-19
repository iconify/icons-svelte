<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ap3nt-pxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":464};
const content = `<path class="ap3nt-pxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:facto" {...props}></Icon>
