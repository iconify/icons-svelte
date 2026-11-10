<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gf6-64bai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gf6-64bai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:ice-pop" {...props}></Icon>
