<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ol0qh5boc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":16};
const content = `<path class="ol0qh5boc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:folder-share" {...props}></Icon>
