<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nth9yctlc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nth9yctlc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:box-tissue" {...props}></Icon>
