<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t83_2skig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t83_2skig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:bell-stroke-20" {...props}></Icon>
