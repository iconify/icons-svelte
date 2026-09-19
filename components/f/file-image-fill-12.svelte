<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jqb09mbio.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="jqb09mbio"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-image-fill-12" {...props}></Icon>
