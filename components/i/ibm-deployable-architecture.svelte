<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xkgx16bwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xkgx16bwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-deployable-architecture" {...props}></Icon>
