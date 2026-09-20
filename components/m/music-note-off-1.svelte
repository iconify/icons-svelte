<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x489fphor.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="x489fphor"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:music-note-off-1" {...props}></Icon>
