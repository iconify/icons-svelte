<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sdziatdzg.css';
import '../../css/r/r_w95gdro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sdziatdzg"/><path class="r_w95gdro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:arrow-in-down-stroke-circle-half" {...props}></Icon>
