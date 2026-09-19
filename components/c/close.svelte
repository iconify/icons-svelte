<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/li6r0m7yr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":304,"height":384};
const content = `<path class="li6r0m7yr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:close" {...props}></Icon>
