<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1kw-cc7c.css';
import '../../css/o/odgrbee8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="m1kw-cc7c"/><rect class="odgrbee8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-pdf-stroke-16" {...props}></Icon>
