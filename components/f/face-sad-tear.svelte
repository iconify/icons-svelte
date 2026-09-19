<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bb0_8-tpv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bb0_8-tpv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:face-sad-tear" {...props}></Icon>
