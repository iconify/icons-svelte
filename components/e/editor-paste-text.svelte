<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xyyhb3b_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xyyhb3b_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dashicons:editor-paste-text" {...props}></Icon>
