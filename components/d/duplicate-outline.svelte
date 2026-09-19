<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x1lbyxb3k.css';
import '../../css/d/ddsbg3vby.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="x1lbyxb3k"/><path class="ddsbg3vby"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:duplicate-outline" {...props}></Icon>
