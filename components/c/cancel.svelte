<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm4gpizxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm4gpizxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:cancel" {...props}></Icon>
