<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7n0xbc9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p7n0xbc9y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:cut" {...props}></Icon>
