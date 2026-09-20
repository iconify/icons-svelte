<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yywrzcbcn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yywrzcbcn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:military-police-officer" {...props}></Icon>
