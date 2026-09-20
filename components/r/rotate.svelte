<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow7mwmbfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ow7mwmbfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:rotate" {...props}></Icon>
