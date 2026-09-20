<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnvbcbe-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rnvbcbe-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:prio-middle" {...props}></Icon>
