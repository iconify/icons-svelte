<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysl5nf33v.css';
import '../../css/v/vjs9accli.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ysl5nf33v"/><path class="vjs9accli"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:edit-undo-fill-16" {...props}></Icon>
