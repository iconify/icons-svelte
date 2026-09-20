<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jgv1q4brx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="jgv1q4brx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-block:nature-water" {...props}></Icon>
