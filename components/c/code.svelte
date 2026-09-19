<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rf_6m0xwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rf_6m0xwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:code" {...props}></Icon>
