<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r57eupb_b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":696,"height":692};
const content = `<path class="r57eupb_b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:copy" {...props}></Icon>
