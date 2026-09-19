<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qdpx68b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="qdpx68b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:netflix" {...props}></Icon>
