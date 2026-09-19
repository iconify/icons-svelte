<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugv1xtbva.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ugv1xtbva"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clone" {...props}></Icon>
