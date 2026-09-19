<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dcxadpb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":18,"height":16};
const content = `<path class="dcxadpb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:keyboard" {...props}></Icon>
