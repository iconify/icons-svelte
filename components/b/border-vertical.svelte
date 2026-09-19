<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_l9mabmc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="p_l9mabmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:border-vertical" {...props}></Icon>
