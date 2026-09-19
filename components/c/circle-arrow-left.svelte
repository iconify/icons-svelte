<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd3reeydg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vd3reeydg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:circle-arrow-left" {...props}></Icon>
