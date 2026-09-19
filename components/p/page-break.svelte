<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmxe8fbjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="cmxe8fbjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:page-break" {...props}></Icon>
