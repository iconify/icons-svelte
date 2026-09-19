<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq6wzaboh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="aq6wzaboh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gears" {...props}></Icon>
