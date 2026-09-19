<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be7pepbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="be7pepbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-pptx" {...props}></Icon>
