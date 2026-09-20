<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ns_wucbxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ns_wucbxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:bladder" {...props}></Icon>
