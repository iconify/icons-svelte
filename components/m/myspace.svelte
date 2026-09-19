<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/znzhc5ozp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="znzhc5ozp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:myspace" {...props}></Icon>
