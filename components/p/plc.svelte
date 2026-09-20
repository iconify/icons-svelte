<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/saf42g1dl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="saf42g1dl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:plc" {...props}></Icon>
