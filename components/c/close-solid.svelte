<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pxk9lbbab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pxk9lbbab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:close-solid" {...props}></Icon>
