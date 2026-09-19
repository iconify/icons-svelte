<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxmzf6d8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="uxmzf6d8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:file-edit" {...props}></Icon>
