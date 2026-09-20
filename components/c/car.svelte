<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv00gzbnl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fv00gzbnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:car" {...props}></Icon>
