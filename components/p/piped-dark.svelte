<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f09tprafk.css';
import '../../css/u/ug7q-clry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f09tprafk"/><path class="ug7q-clry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piped-dark" {...props}></Icon>
