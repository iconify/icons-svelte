<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkuwb95yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wkuwb95yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:arrow-down" {...props}></Icon>
