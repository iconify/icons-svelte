<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ik5l8_l-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ik5l8_l-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:data-board" {...props}></Icon>
