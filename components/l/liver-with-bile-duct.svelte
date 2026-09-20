<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gyojgbk_j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gyojgbk_j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:liver-with-bile-duct" {...props}></Icon>
