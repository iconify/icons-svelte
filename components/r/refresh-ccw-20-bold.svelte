<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yv5tshbbx.css';
import '../../css/b/b7nj-761u.css';
import '../../css/n/ndokbv5ou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yv5tshbbx"/><path class="b7nj-761u"/><path class="ndokbv5ou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:refresh-ccw-20-bold" {...props}></Icon>
