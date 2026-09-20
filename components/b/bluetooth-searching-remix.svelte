<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdl14fb2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fdl14fb2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:bluetooth-searching-remix" {...props}></Icon>
