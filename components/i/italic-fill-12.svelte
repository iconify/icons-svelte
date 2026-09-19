<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywdlqebgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ywdlqebgr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:italic-fill-12" {...props}></Icon>
