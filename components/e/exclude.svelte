<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oexwgpb2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="oexwgpb2j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:exclude" {...props}></Icon>
