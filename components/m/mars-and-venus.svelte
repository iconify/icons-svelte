<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/luow4-bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="luow4-bey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:mars-and-venus" {...props}></Icon>
