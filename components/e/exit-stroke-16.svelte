<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm5tpccqz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="fm5tpccqz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:exit-stroke-16" {...props}></Icon>
