<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy8a-7mcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oy8a-7mcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:paintbrush" {...props}></Icon>
