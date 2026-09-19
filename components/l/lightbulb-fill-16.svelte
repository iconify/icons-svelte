<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_md5nbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j_md5nbmj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:lightbulb-fill-16" {...props}></Icon>
