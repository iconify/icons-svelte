<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vfwz52s2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vfwz52s2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:gift" {...props}></Icon>
