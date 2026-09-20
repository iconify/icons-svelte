<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_7jfibdt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="j_7jfibdt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:music-note-circle-remix" {...props}></Icon>
