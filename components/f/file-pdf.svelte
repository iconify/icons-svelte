<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-uv_2n-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="p-uv_2n-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:file-pdf" {...props}></Icon>
