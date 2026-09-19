<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lt7kltbjs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="lt7kltbjs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:grin-wink" {...props}></Icon>
