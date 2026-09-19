<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ylo1qp7ot.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ylo1qp7ot"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:arrow-left" {...props}></Icon>
