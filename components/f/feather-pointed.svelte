<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o72rlybrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="o72rlybrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:feather-pointed" {...props}></Icon>
