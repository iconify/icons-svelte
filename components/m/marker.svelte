<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zgs12i4vt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="zgs12i4vt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:marker" {...props}></Icon>
