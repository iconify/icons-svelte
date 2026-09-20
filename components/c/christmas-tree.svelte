<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-neo8bea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d-neo8bea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:christmas-tree" {...props}></Icon>
