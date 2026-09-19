<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-h-ppb6d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="d-h-ppb6d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:bookmark" {...props}></Icon>
