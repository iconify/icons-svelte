<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h-oq19vel.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="h-oq19vel"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:file-pdf-outline" {...props}></Icon>
