<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mcg3ghv9p.css';
import '../../css/j/j85tku0cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="mcg3ghv9p"/><path class="j85tku0cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:code-alt" {...props}></Icon>
