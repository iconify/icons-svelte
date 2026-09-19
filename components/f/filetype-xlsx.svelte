<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/duh_o4gwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="duh_o4gwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:filetype-xlsx" {...props}></Icon>
