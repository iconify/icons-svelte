<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j972wnbjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="j972wnbjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:chart-bar-circle" {...props}></Icon>
