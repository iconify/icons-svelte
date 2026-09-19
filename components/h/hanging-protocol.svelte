<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fzul08b9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fzul08b9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:hanging-protocol" {...props}></Icon>
