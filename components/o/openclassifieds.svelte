<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn72qbjmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1023};
const content = `<path class="xn72qbjmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:openclassifieds" {...props}></Icon>
