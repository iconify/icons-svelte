<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yolz4bbbs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="yolz4bbbs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:d" {...props}></Icon>
