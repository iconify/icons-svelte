<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hd9rnlwhz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="hd9rnlwhz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:kebab-horizontal-16" {...props}></Icon>
