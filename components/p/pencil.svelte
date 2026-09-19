<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yfo7-6c4c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":42,"height":42};
const content = `<path class="yfo7-6c4c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="topcoat:pencil" {...props}></Icon>
