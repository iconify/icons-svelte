<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/re6ijgajr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="re6ijgajr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:list-numbered" {...props}></Icon>
