<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oj4co0bsz.css';
import '../../css/a/aaj4a2bie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="oj4co0bsz"/><path class="aaj4a2bie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="temaki:mast-lighting" {...props}></Icon>
