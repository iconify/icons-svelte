<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_jxjbi0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="g_jxjbi0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:car" {...props}></Icon>
