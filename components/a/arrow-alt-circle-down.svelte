<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9rh5p0qp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="j9rh5p0qp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:arrow-alt-circle-down" {...props}></Icon>
