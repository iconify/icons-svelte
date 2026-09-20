<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqe_5emhp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="hqe_5emhp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:post-box" {...props}></Icon>
