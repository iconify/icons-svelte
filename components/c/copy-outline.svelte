<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1lbyxb3k.css';
import '../../css/p/p-t5oux0e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="x1lbyxb3k"/><path class="p-t5oux0e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:copy-outline" {...props}></Icon>
