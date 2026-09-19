<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vqcjrk-gv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":512};
const content = `<path class="vqcjrk-gv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-brands:gripfire" {...props}></Icon>
