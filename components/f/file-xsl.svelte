<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/af-2b-5_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="af-2b-5_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:file-xsl" {...props}></Icon>
