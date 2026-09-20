<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cr7bvf8cg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="cr7bvf8cg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:crane-hook-16" {...props}></Icon>
