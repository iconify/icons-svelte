<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ucghxkb5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ucghxkb5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:person-tow-skiing-on-water" {...props}></Icon>
