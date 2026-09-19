<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxijxzs2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":488,"height":496};
const content = `<path class="uxijxzs2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:brightness-high" {...props}></Icon>
