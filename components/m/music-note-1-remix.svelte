<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6d1w-b2l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="q6d1w-b2l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-note-1-remix" {...props}></Icon>
