<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxr5szb8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1136.55,"height":1136.55};
const content = `<path class="zxr5szb8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:roborock" {...props}></Icon>
