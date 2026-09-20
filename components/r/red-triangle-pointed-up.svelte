<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zo1g7xbzh.css';
import '../../css/y/yvaz16bmf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="zo1g7xbzh"/><path class="yvaz16bmf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:red-triangle-pointed-up" {...props}></Icon>
