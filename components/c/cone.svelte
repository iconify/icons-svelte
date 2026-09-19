<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qiw2f8g6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="qiw2f8g6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:cone" {...props}></Icon>
