<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aq_fs4hmx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="aq_fs4hmx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:nim" {...props}></Icon>
