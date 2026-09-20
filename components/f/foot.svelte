<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f3cemgbmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="f3cemgbmd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:foot" {...props}></Icon>
