<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1_5a4buf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p1_5a4buf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:pause" {...props}></Icon>
