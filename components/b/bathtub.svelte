<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ph3t2ifho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ph3t2ifho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:bathtub" {...props}></Icon>
