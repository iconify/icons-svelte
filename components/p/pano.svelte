<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kbhx81bpm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="kbhx81bpm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:pano" {...props}></Icon>
