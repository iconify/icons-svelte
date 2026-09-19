<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e_-cg7b6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":730};
const content = `<path class="e_-cg7b6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:key" {...props}></Icon>
