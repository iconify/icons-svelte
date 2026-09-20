<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9yn4-b8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j9yn4-b8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:picoshare" {...props}></Icon>
