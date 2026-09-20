<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbxi8usrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tbxi8usrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:europris-light" {...props}></Icon>
