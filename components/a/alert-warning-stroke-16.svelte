<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ur6ybxbzg.css';
import '../../css/p/p9hlq3xpn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ur6ybxbzg"/><circle class="p9hlq3xpn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:alert-warning-stroke-16" {...props}></Icon>
