<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf2eqxbvf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="bf2eqxbvf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:picture-off-filled" {...props}></Icon>
