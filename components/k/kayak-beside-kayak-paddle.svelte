<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zp59d6b8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zp59d6b8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:kayak-beside-kayak-paddle" {...props}></Icon>
