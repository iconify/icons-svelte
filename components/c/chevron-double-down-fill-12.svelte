<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bm7bzwy4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="bm7bzwy4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:chevron-double-down-fill-12" {...props}></Icon>
