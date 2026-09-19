<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxdr3cc4r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":224,"height":472};
const content = `<path class="cxdr3cc4r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:next" {...props}></Icon>
