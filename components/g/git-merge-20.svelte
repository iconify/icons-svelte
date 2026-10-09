<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgbvxq5ir.css';
import '../../css/r/r7c5xu-gz.css';
import '../../css/t/to374yt6r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="rgbvxq5ir"/><path class="r7c5xu-gz"/><path class="to374yt6r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:git-merge-20" {...props}></Icon>
