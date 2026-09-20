<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a_yatmezl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="a_yatmezl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:milk-carton-and-apple" {...props}></Icon>
