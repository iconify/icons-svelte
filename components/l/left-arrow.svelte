<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vcc4ktbbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vcc4ktbbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:left-arrow" {...props}></Icon>
