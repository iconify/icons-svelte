<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw7vg6b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":512};
const content = `<path class="zw7vg6b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:caret-right" {...props}></Icon>
