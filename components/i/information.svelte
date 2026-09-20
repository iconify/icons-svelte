<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wh32qp8wm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wh32qp8wm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pajamas:information" {...props}></Icon>
