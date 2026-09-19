<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuv29vqrx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tuv29vqrx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:golf-club" {...props}></Icon>
