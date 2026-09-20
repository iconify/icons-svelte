<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z_qsx6bnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z_qsx6bnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="subway:book" {...props}></Icon>
