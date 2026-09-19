<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<polygon points="2.75 2.75 2.75 13.25 12.25 8" class="hntgybcog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:media-play" {...props}></Icon>
