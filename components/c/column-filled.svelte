<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x50h0pbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x50h0pbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:column-filled" {...props}></Icon>
