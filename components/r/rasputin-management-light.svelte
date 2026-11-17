<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pyg63gb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pyg63gb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:rasputin-management-light" {...props}></Icon>
