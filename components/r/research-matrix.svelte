<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ozprgdw2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ozprgdw2n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:research-matrix" {...props}></Icon>
