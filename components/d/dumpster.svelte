<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n_-8tnb_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="n_-8tnb_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:dumpster" {...props}></Icon>
