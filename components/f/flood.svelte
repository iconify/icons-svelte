<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i7_hf0wim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="i7_hf0wim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:flood" {...props}></Icon>
