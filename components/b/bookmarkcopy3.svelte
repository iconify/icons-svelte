<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t9i3q3b6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="t9i3q3b6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:bookmarkcopy3" {...props}></Icon>
