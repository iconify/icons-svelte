<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpd7mvmhe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mpd7mvmhe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:document-add" {...props}></Icon>
