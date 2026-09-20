<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bstajwh4p.css';
import '../../css/f/fbeehkbqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bstajwh4p"/><path class="fbeehkbqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:music-speaker" {...props}></Icon>
