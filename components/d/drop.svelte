<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s_tdev-jz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":328,"height":496};
const content = `<path class="s_tdev-jz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:drop" {...props}></Icon>
