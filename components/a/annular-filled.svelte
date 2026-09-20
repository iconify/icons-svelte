<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e4qxcbkkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="e4qxcbkkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:annular-filled" {...props}></Icon>
