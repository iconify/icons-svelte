<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vguk4jb4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vguk4jb4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:edit" {...props}></Icon>
