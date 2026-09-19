<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a2_ijpk0w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="a2_ijpk0w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:clapperboard" {...props}></Icon>
