<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tunbnrbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tunbnrbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:pointer-left" {...props}></Icon>
