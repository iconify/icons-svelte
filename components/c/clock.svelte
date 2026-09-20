<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mbwe8e7vg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mbwe8e7vg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:clock" {...props}></Icon>
