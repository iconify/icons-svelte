<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmj4v3web.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":432};
const content = `<path class="jmj4v3web"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:comment-alt" {...props}></Icon>
