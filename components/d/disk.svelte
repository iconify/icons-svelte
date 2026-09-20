<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hjrs9xcdk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hjrs9xcdk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:disk" {...props}></Icon>
