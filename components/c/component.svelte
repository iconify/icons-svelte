<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2tiyibie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k2tiyibie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:component" {...props}></Icon>
