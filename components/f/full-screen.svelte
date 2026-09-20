<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc9fjabnv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="zc9fjabnv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:full-screen" {...props}></Icon>
