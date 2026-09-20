<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt03rbywx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dt03rbywx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:parking-space" {...props}></Icon>
