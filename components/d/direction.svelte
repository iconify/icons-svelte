<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0nvg9_ro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n0nvg9_ro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:direction" {...props}></Icon>
