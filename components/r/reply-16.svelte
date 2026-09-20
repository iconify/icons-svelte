<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-ns_tb3a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="r-ns_tb3a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:reply-16" {...props}></Icon>
