<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5xhfbbdq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u5xhfbbdq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:music-note-1-flat" {...props}></Icon>
