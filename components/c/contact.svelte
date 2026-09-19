<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjnv3rbuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="rjnv3rbuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:contact" {...props}></Icon>
