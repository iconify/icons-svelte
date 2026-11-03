<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c815m4b3j.css';
import '../../css/x/xizs9ebfh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="c815m4b3j"/><path class="xizs9ebfh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kept-inventory" {...props}></Icon>
