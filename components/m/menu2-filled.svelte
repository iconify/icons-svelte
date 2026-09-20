<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1ag7wbxs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="y1ag7wbxs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:menu2-filled" {...props}></Icon>
