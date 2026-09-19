<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xx-7mnbkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xx-7mnbkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:movie-play" {...props}></Icon>
