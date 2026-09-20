<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow0w91b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ow0w91b8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:music-note-trebble-clef" {...props}></Icon>
