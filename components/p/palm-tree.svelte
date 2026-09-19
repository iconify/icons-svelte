<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nzt0k9bvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nzt0k9bvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:palm-tree" {...props}></Icon>
