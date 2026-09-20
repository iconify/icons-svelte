<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nj8ql5dfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="nj8ql5dfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cup-and-saucer-and-pawprint" {...props}></Icon>
