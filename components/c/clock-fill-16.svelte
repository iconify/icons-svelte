<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1kt5xcuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="p1kt5xcuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:clock-fill-16" {...props}></Icon>
