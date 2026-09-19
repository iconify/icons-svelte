<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qd34l8bbv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="qd34l8bbv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:land-mine-on" {...props}></Icon>
