<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7_s0d79d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="e7_s0d79d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-brands:get-pocket" {...props}></Icon>
