<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn80i1bxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="rn80i1bxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-txt-filled" {...props}></Icon>
