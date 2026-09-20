<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cu23513nj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cu23513nj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:apps-filled" {...props}></Icon>
