<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozkx9c3gg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="ozkx9c3gg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:deviantart" {...props}></Icon>
