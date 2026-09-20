<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ezm5o3bwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ezm5o3bwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:add-one-filled" {...props}></Icon>
