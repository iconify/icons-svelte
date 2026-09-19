<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxlzlfbum.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dxlzlfbum"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-square-fill" {...props}></Icon>
