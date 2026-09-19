<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zme58pbcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="zme58pbcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dumpster-fire" {...props}></Icon>
