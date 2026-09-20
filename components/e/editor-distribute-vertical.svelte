<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xwum7jbph.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xwum7jbph"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:editor-distribute-vertical" {...props}></Icon>
