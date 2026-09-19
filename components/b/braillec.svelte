<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h0rrt-0dx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":1024};
const content = `<path class="h0rrt-0dx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:braillec" {...props}></Icon>
