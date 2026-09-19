<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg_5oxbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="dg_5oxbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:chat-right-heart-fill" {...props}></Icon>
