<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4qgvpbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="z4qgvpbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:coffin-with-flaming-chalice" {...props}></Icon>
