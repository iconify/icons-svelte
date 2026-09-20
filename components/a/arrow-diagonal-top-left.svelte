<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm_c2mbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wm_c2mbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-diagonal-top-left" {...props}></Icon>
