<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsomw9b0p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="fsomw9b0p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:recycle-bin-2-remix" {...props}></Icon>
