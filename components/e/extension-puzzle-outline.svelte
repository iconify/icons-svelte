<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpiskl3ii.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cpiskl3ii"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:extension-puzzle-outline" {...props}></Icon>
