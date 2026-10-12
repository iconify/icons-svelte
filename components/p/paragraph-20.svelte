<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc9t6kiho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dc9t6kiho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:paragraph-20" {...props}></Icon>
