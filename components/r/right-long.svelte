<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aw46uobjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="aw46uobjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:right-long" {...props}></Icon>
