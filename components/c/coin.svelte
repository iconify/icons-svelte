<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2ho5fb2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="i2ho5fb2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:coin" {...props}></Icon>
