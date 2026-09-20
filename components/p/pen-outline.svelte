<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oy2a6pbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oy2a6pbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pen-outline" {...props}></Icon>
