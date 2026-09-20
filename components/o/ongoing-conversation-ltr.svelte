<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p2gyfudfs.css';
import '../../css/b/b5kui9phr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="p2gyfudfs"/><path class="b5kui9phr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:ongoing-conversation-ltr" {...props}></Icon>
