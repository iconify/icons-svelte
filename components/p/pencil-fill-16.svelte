<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ag5e9zx_f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ag5e9zx_f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:pencil-fill-16" {...props}></Icon>
