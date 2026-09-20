<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz5j96neh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="uz5j96neh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rocky-linux-light" {...props}></Icon>
