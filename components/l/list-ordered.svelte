<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n9_1nzbyt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="n9_1nzbyt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="at-icons:list-ordered" {...props}></Icon>
