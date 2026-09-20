<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/ptedp6bhh.css';
import '../../css/x/xat9ymb7w.css';
import '../../css/t/thrb5hbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":116};
const content = `<path class="ptedp6bhh"/><path class="xat9ymb7w"/><path class="thrb5hbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:cloudflare" {...props}></Icon>
