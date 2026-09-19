<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnpnmxbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="dnpnmxbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:daydream-setting" {...props}></Icon>
