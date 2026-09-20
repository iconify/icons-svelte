<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mhx1nlb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="mhx1nlb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:reorder" {...props}></Icon>
