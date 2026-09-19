<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ba5lbhb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="l8ba5lbhb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:arrows-up-down-left-right" {...props}></Icon>
