<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r7tbgfbbp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r7tbgfbbp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:hand-right-sharp" {...props}></Icon>
