<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b3s5gsb_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="b3s5gsb_s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-undo" {...props}></Icon>
