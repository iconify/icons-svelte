<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5cov6bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v5cov6bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:bell" {...props}></Icon>
