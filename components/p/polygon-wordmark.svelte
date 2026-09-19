<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a-o-n6vfd.css';
import '../../css/h/hq6p7itxj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="a-o-n6vfd"/><path class="hq6p7itxj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:polygon-wordmark" {...props}></Icon>
