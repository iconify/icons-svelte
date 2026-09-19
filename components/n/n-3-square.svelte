<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_0mflbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="s_0mflbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:n-3-square" {...props}></Icon>
