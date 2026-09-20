<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxveumuww.css';
import '../../css/d/dekf_bboy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="wxveumuww"/><path class="dekf_bboy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:reply-all-16" {...props}></Icon>
